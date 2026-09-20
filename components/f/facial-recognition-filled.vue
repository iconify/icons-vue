<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxukx6b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxukx6b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:facial-recognition-filled" /></template>
