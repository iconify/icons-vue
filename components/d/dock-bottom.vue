<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mssb4p5se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mssb4p5se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:dock-bottom" /></template>
