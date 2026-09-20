<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_eq3mbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_eq3mbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-add2" /></template>
