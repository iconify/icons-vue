<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8r7dteuj.css';
import '../../css/s/sktgnkdka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8r7dteuj"/><path class="sktgnkdka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-pouch-48-bold" /></template>
