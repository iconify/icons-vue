<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyvviob6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyvviob6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:flame" /></template>
