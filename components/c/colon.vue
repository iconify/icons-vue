<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaw-bkn7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uaw-bkn7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:colon" /></template>
