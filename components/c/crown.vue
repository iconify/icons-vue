<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx1b0tbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx1b0tbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:crown" /></template>
