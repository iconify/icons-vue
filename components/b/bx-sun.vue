<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm0e28bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm0e28bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-sun" /></template>
