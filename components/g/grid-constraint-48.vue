<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpcjzhb8z.css';
import '../../css/i/in0d74b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rpcjzhb8z"/><path class="in0d74b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-constraint-48" /></template>
