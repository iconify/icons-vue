<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oryyolw3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oryyolw3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:landscape" /></template>
