<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vapdjacjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vapdjacjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clover-fill-round" /></template>
