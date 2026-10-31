<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f31cmbbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f31cmbbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-down-large-fill-round" /></template>
