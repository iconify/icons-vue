<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecsrbub4u.css';
import '../../css/m/mnlk1ccyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ecsrbub4u"/><path class="mnlk1ccyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:chart-bar" /></template>
