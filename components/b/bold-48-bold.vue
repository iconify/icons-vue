<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwduy1bns.css';
import '../../css/k/kuz80_b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mwduy1bns"/><path class="kuz80_b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bold-48-bold" /></template>
