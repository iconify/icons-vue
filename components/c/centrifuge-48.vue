<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl-lwcbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sl-lwcbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:centrifuge-48" /></template>
