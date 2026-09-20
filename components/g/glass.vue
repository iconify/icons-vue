<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys4jh9bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys4jh9bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:glass" /></template>
