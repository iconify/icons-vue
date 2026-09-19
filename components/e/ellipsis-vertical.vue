<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3fjp7b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":512};
const content = `<path class="f3fjp7b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:ellipsis-vertical" /></template>
