<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7tua87xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7tua87xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-square-thin" /></template>
