<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs68q0byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vs68q0byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:calendar-add-solid" /></template>
