<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxz5dobuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":1408};
const content = `<path class="oxz5dobuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:ellipsis-v" /></template>
