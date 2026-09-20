<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey3bs5pmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey3bs5pmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevron-down-sharp-fill" /></template>
