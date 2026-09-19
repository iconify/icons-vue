<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub_o4lqpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ub_o4lqpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:alcohol" /></template>
