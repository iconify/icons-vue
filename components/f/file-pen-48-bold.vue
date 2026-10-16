<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjdu4dbzy.css';
import '../../css/d/djhyfvqnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pjdu4dbzy"/><path class="djhyfvqnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-pen-48-bold" /></template>
