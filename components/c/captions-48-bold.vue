<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8314acox.css';
import '../../css/s/sy3lcl67n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8314acox"/><path class="sy3lcl67n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:captions-48-bold" /></template>
