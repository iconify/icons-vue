<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3un3_8gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3un3_8gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:film-roll" /></template>
