<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-7mmbagi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-7mmbagi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:antigravity-google" /></template>
