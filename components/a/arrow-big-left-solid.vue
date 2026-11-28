<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kca4iibme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kca4iibme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-left-solid" /></template>
