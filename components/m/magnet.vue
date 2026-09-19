<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud904hvzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud904hvzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:magnet" /></template>
