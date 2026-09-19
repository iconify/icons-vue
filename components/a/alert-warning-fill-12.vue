<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i136-euic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="i136-euic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alert-warning-fill-12" /></template>
