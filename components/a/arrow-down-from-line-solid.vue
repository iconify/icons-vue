<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8j94bzho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8j94bzho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-down-from-line-solid" /></template>
