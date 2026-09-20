<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvevkhbsd.css';
import '../../css/f/fnx5s2bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvevkhbsd"/><path class="fnx5s2bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:color-palette-sample-2" /></template>
