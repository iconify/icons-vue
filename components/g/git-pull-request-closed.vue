<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjaqj1fxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjaqj1fxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-pull-request-closed" /></template>
