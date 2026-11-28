<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nemrsnj0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nemrsnj0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:file-question-thin" /></template>
