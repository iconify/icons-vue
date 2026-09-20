<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy3f9p5rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xy3f9p5rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calculator2-filled" /></template>
