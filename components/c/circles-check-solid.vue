<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_cxg8bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_cxg8bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circles-check-solid" /></template>
