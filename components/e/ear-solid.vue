<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcp738b4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcp738b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ear-solid" /></template>
