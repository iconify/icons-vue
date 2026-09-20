<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-zv0sbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-zv0sbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flight-landing-filled" /></template>
