<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_pz3rxhk.css';
import '../../css/f/fh_lgcbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y_pz3rxhk"/><path class="fh_lgcbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-code-48-bold" /></template>
