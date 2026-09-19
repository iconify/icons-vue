<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h13n8sbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":216,"height":488};
const content = `<path class="h13n8sbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:instapaper" /></template>
