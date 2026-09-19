<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9maj33kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9maj33kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-right-stroke-square-filled" /></template>
