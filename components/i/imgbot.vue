<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu0yxyb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":360,"height":512};
const content = `<path class="vu0yxyb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:imgbot" /></template>
