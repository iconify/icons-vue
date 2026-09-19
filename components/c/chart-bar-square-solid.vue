<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hov6vy65m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hov6vy65m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chart-bar-square-solid" /></template>
