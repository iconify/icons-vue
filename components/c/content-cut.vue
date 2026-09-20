<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm8x86b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm8x86b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:content-cut" /></template>
