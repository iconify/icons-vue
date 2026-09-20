<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5jusru4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w5jusru4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-outline" /></template>
