<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjmp-sxcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjmp-sxcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-finger-line" /></template>
