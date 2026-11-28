<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0b_y1bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0b_y1bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:laurel-wreath-solid" /></template>
