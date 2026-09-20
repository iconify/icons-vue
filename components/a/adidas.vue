<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd4u15bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd4u15bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:adidas" /></template>
