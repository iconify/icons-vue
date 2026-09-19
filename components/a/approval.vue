<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfwf8-3ye.css';
import '../../css/a/az0bq2bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wfwf8-3ye"/><path class="az0bq2bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:approval" /></template>
