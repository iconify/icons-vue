<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdqx3fz-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vdqx3fz-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-chip-1" /></template>
