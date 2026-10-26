<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amaq5lbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="amaq5lbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:chevron-left" /></template>
