<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_msvzj4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="h_msvzj4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:chain" /></template>
