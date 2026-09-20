<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbtu1bbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tbtu1bbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:javaclass" /></template>
