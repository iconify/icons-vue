<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in2o_h8de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="in2o_h8de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:align-right" /></template>
