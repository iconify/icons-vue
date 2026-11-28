<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a73y-rygy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="a73y-rygy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:chart-area-light" /></template>
