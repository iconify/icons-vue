<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je626mxyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="je626mxyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-x-solid" /></template>
