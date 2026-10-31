<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqcyeib-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqcyeib-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cylinder-fill-round" /></template>
