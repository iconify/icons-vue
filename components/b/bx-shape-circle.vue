<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh27ejb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh27ejb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-shape-circle" /></template>
