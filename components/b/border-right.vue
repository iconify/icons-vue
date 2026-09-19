<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq4os3blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq4os3blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:border-right" /></template>
