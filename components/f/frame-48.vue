<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8tp9mb-t.css';
import '../../css/b/bju7mh2fw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l8tp9mb-t"/><path class="bju7mh2fw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frame-48" /></template>
