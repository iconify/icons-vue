<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j10_t9shp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j10_t9shp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-imac-spark" /></template>
