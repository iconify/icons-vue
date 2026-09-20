<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwrqe-bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwrqe-bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:liberapay" /></template>
