<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkftr6bal.css';
import '../../css/o/of7e8kpvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkftr6bal"/><path class="of7e8kpvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-camera" /></template>
