<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpr64obko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpr64obko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-first-page" /></template>
