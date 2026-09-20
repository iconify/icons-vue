<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tevga6bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tevga6bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adminer-dark" /></template>
