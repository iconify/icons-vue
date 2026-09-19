<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av0dlcsdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="av0dlcsdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:chevron-collapse-outline" /></template>
