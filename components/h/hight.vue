<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx5yaihwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tx5yaihwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:hight" /></template>
