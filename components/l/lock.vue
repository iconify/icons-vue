<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq0i8qkjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq0i8qkjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:lock" /></template>
