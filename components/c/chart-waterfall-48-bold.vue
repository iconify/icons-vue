<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghe6iqpty.css';
import '../../css/f/fqoptnsed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ghe6iqpty"/><path class="fqoptnsed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-waterfall-48-bold" /></template>
