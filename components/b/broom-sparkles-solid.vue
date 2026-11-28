<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez8p2nbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez8p2nbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:broom-sparkles-solid" /></template>
