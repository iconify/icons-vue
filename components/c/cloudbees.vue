<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj2gl92lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj2gl92lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cloudbees" /></template>
