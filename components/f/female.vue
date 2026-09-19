<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk-mk3b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":192,"height":432};
const content = `<path class="wk-mk3b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:female" /></template>
