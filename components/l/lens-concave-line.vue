<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3_zluyok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3_zluyok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lens-concave-line" /></template>
