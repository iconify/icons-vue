<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg-0wkbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg-0wkbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:desktop-tower-x" /></template>
