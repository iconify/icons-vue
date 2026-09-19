<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg7wyab-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tg7wyab-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:grip" /></template>
