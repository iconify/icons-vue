<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shpzc8bzi.css';
import '../../css/h/h9q4084iu.css';
import '../../css/p/pj3y1bc7z.css';
import '../../css/u/u-y_iqbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shpzc8bzi"/><path class="h9q4084iu"/><path class="pj3y1bc7z"/><path class="u-y_iqbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:chrome" /></template>
