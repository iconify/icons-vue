<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9tmg2wym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k9tmg2wym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:clipboard-check-bold" /></template>
