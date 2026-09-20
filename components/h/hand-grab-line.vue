<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3ft6gpyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3ft6gpyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-grab-line" /></template>
