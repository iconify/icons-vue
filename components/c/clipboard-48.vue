<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-s18fbbr.css';
import '../../css/p/p0vii7b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x-s18fbbr"/><path class="p0vii7b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-48" /></template>
