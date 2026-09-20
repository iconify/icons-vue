<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfnwn2btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfnwn2btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:immer" /></template>
