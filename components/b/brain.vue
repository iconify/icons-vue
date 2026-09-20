<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exjne1qug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="exjne1qug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:brain" /></template>
