<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1t2i0p0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1t2i0p0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:autozone" /></template>
