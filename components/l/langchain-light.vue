<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tant6eb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":120,"height":120};
const content = `<path class="tant6eb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:langchain-light" /></template>
