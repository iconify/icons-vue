<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs3rl09dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xs3rl09dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:exmo" /></template>
