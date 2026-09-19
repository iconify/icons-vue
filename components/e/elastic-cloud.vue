<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_jo19bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s_jo19bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:elastic-cloud" /></template>
