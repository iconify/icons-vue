<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5tn3lm6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary v5tn3lm6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-graph-duotone" /></template>
