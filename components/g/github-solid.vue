<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki94p-fap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki94p-fap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:github-solid" /></template>
