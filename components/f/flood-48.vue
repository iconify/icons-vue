<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daa8iq9kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="daa8iq9kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flood-48" /></template>
