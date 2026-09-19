<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7g3dsb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32,"left":1};
const content = `<path class="x7g3dsb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:eop" /></template>
