<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbnv7fbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbnv7fbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-fortress" /></template>
