<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp5n-8bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp5n-8bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:duplicati" /></template>
