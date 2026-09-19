<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id8_52b1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="id8_52b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ctr" /></template>
