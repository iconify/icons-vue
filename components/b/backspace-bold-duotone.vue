<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oeqs3cbpz.css';
import '../../css/f/fvpx17bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oeqs3cbpz"/><path class="fvpx17bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:backspace-bold-duotone" /></template>
