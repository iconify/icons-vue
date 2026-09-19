<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z38k6nb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z38k6nb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:flip-horizontal-outline" /></template>
