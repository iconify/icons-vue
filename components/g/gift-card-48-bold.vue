<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8314acox.css';
import '../../css/j/jk0_mdbae.css';
import '../../css/d/d55bptbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8314acox"/><path class="jk0_mdbae"/><path class="d55bptbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gift-card-48-bold" /></template>
