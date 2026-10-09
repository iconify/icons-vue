<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax49_hbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ax49_hbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevron-right-48" /></template>
