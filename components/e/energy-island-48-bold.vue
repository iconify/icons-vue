<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu1gnobxb.css';
import '../../css/r/r_8asobqy.css';
import '../../css/f/fwij3dbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wu1gnobxb"/><path class="r_8asobqy"/><path class="fwij3dbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-island-48-bold" /></template>
