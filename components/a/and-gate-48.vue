<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqsl-cq4l.css';
import '../../css/r/rzc5_66zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mqsl-cq4l"/><path class="rzc5_66zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:and-gate-48" /></template>
