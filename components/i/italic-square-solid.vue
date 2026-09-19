<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eojy44boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eojy44boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:italic-square-solid" /></template>
