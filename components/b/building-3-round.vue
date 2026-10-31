<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qduqn3niy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qduqn3niy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-3-round" /></template>
