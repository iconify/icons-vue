<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz13tcbgt.css';
import '../../css/h/h6zvdsy7j.css';
import '../../css/k/kymxsbbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cz13tcbgt"/><path class="h6zvdsy7j"/><path class="kymxsbbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-landing-48-bold" /></template>
