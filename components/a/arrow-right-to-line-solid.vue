<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrcg_m-ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrcg_m-ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-right-to-line-solid" /></template>
