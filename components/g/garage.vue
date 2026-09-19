<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy9biv73g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy9biv73g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:garage" /></template>
