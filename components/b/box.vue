<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd6f9ccio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jd6f9ccio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box" /></template>
