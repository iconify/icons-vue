<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i339vabyb.css';
import '../../css/g/gtfr4-buh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i339vabyb"/><path class="gtfr4-buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:drawer-image" /></template>
