<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a05ngs8sl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a05ngs8sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:internet-explorer" /></template>
