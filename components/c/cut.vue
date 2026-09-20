<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmg620o6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vmg620o6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:cut" /></template>
