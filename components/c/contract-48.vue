<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljxy0pbpp.css';
import '../../css/t/t2peqlb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ljxy0pbpp"/><path class="t2peqlb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contract-48" /></template>
