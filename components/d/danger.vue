<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlfa2ebbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="dlfa2ebbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:danger" /></template>
