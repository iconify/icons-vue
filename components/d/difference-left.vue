<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csg993q7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csg993q7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:difference-left" /></template>
