<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjg8m-bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjg8m-bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:android" /></template>
