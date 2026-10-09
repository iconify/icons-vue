<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/defz0cbcm.css';
import '../../css/k/khp0jolrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="defz0cbcm"/><path class="khp0jolrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-48-bold" /></template>
