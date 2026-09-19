<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfh0mccvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="bfh0mccvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:expand" /></template>
