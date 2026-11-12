<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu7gz6_gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uu7gz6_gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dagster-dark" /></template>
