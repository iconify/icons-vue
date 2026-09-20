<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns28zkbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ns28zkbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:electric-cord-1-solid" /></template>
