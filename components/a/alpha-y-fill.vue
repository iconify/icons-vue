<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi41ctbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wi41ctbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-y-fill" /></template>
