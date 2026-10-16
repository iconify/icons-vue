<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zen2agbyu.css';
import '../../css/v/v53qj5w7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zen2agbyu"/><path class="v53qj5w7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:disc-48" /></template>
