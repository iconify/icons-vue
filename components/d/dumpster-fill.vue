<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emr687pzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="emr687pzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:dumpster-fill" /></template>
