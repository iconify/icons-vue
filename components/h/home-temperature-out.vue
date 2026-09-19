<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxo7j6bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxo7j6bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:home-temperature-out" /></template>
