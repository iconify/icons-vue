<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu17u970l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu17u970l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lollipop-fill" /></template>
