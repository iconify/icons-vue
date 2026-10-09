<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cywpx4aix.css';
import '../../css/p/pqk-h9_8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cywpx4aix"/><path class="pqk-h9_8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:brush-48-bold" /></template>
