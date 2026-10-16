<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moyoz5fkv.css';
import '../../css/e/e3q-l4bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="moyoz5fkv"/><path class="e3q-l4bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-gbt-48-bold" /></template>
