<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm7ljybas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nm7ljybas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:fingerprint" /></template>
