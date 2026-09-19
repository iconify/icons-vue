<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tduyn620x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tduyn620x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:exercise-yoga" /></template>
