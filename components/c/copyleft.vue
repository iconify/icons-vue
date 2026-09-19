<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynhhlqb6o.css';
import '../../css/c/cfetz3bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ynhhlqb6o"/><path class="cfetz3bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:copyleft" /></template>
