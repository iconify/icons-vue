<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwb5ovbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwb5ovbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-codepen" /></template>
