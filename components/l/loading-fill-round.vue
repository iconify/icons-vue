<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6hm1qwau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6hm1qwau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loading-fill-round" /></template>
