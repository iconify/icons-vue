<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t10i58gej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="t10i58gej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:exercise-yoga-outline" /></template>
