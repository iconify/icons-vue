<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usqlzhh8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usqlzhh8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-left-stroke-square-filled" /></template>
