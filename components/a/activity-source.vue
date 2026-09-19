<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swn4cmbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="swn4cmbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:activity-source" /></template>
