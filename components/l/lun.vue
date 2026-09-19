<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig3pv1hce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ig3pv1hce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:lun" /></template>
