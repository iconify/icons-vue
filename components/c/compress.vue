<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t13bcodxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="t13bcodxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:compress" /></template>
