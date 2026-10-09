<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w98uktbvf.css';
import '../../css/e/e3n-urbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w98uktbvf"/><path class="e3n-urbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ice-cream-48-bold" /></template>
