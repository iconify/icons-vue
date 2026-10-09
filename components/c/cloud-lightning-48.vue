<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlah_2byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlah_2byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-lightning-48" /></template>
