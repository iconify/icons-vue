<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jblz62buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jblz62buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:electricity" /></template>
