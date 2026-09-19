<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crmd8sbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crmd8sbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:add-to-queue" /></template>
