<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awxwfdbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awxwfdbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:magnifying-glass-plus" /></template>
