<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn4b-obfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn4b-obfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bot-x" /></template>
