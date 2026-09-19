<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-xikmwof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="d-xikmwof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:backspace" /></template>
