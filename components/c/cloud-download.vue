<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dah10_0uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1408};
const content = `<path class="dah10_0uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cloud-download" /></template>
