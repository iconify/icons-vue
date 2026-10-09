<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-4rqjbfm.css';
import '../../css/h/h1xc_8yrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t-4rqjbfm"/><path class="h1xc_8yrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-network-48-bold" /></template>
