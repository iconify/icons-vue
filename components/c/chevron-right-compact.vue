<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhx61zfib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fhx61zfib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chevron-right-compact" /></template>
