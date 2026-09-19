<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tte_n1llm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tte_n1llm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-left" /></template>
