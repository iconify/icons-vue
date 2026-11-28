<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb05hsmgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb05hsmgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bowling-solid" /></template>
