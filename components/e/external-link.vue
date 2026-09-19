<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1f7-bc3e.css';
import '../../css/q/qf2khhs5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="e1f7-bc3e"/><path class="qf2khhs5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:external-link" /></template>
