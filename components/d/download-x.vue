<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o886_iy8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o886_iy8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:download-x" /></template>
