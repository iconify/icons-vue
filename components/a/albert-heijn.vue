<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbt4c8ptk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbt4c8ptk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:albert-heijn" /></template>
