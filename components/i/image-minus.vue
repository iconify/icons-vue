<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu7segb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu7segb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-minus" /></template>
