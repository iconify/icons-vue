<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uchecvbgp.css';
import '../../css/s/sryd7gbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uchecvbgp"/><path class="sryd7gbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gear-48-bold" /></template>
