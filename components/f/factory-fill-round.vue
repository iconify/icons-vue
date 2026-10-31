<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nogaml5-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nogaml5-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:factory-fill-round" /></template>
