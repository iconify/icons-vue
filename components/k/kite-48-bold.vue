<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvli3kbsk.css';
import '../../css/j/j2_5lrbxi.css';
import '../../css/p/pj0row0jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pvli3kbsk"/><path class="j2_5lrbxi"/><path class="pj0row0jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kite-48-bold" /></template>
