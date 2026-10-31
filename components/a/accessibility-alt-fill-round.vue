<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj3nw3btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj3nw3btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:accessibility-alt-fill-round" /></template>
