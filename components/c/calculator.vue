<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts1854bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ts1854bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:calculator" /></template>
