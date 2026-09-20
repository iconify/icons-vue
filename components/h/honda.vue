<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yje1y7w0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yje1y7w0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:honda" /></template>
