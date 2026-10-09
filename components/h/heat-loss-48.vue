<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nod0a6b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nod0a6b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-loss-48" /></template>
