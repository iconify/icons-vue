<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg5ix7bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg5ix7bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:codesignal" /></template>
