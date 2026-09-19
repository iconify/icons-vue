<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flpa9tb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1536};
const content = `<path class="flpa9tb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:download" /></template>
