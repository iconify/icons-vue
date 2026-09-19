<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta22xjbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":718,"height":690};
const content = `<path class="ta22xjbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:amazon" /></template>
