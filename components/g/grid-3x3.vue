<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjeey1y5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjeey1y5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-3x3" /></template>
