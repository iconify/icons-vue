<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvz99qbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvz99qbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flood-48-bold" /></template>
