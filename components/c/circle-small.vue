<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he9jgm06g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="he9jgm06g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:circle-small" /></template>
