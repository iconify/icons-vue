<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn87n_bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qn87n_bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:checked" /></template>
