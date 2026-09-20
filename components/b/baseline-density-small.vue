<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/citcrmigd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="citcrmigd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:baseline-density-small" /></template>
