<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6u-kgb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6u-kgb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:home-plus" /></template>
