<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj7j51b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj7j51b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-text" /></template>
