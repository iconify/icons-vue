<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjqb15sao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sjqb15sao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:lock" /></template>
