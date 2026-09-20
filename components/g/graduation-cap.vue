<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7dw4obsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7dw4obsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:graduation-cap" /></template>
