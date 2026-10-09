<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm5htjbev.css';
import '../../css/u/u247rkkct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tm5htjbev"/><path class="u247rkkct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electrolyser-20-bold" /></template>
