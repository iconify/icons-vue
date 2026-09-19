<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq4jlwbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mq4jlwbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:circles-seven" /></template>
