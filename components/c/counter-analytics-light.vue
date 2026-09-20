<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9r61plyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s9r61plyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:counter-analytics-light" /></template>
