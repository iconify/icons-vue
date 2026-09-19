<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8zxhs7lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p8zxhs7lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-up-outline" /></template>
