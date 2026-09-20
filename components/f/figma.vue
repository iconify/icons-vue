<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u78usi47j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u78usi47j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:figma" /></template>
