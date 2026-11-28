<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9cm2bbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9cm2bbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grid-3x3-solid" /></template>
