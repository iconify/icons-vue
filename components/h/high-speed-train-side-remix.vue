<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnd-t-bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rnd-t-bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:high-speed-train-side-remix" /></template>
