<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru6q8rbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru6q8rbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:book-add" /></template>
