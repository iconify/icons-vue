<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhh5q_bxg.css';
import '../../css/i/il5efkf8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uhh5q_bxg"/><path class="il5efkf8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:control-panel-48" /></template>
