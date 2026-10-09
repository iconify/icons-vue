<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhf9xbb9t.css';
import '../../css/x/xnv-ktb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yhf9xbb9t"/><path class="xnv-ktb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badge-48-bold" /></template>
