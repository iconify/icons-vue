<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siuiveb8v.css';
import '../../css/u/uz5vufbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="siuiveb8v"/><path class="uz5vufbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alert-48" /></template>
