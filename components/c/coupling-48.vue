<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6c7rh25t.css';
import '../../css/r/roygfgbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a6c7rh25t"/><path class="roygfgbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coupling-48" /></template>
