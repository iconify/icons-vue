<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2uy8o19f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2uy8o19f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:base-station-line" /></template>
