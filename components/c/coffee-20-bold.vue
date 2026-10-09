<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsm6o3u7u.css';
import '../../css/u/uw4qzh0ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lsm6o3u7u"/><path class="uw4qzh0ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coffee-20-bold" /></template>
