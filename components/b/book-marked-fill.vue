<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyl-lskto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyl-lskto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-marked-fill" /></template>
