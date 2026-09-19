<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1w7zg6hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u1w7zg6hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bluetooth-b" /></template>
