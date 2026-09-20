<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0gee4-iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g0gee4-iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-curvy-up-down-1-flat" /></template>
