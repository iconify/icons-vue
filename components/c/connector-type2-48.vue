<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj-uuaceq.css';
import '../../css/t/ta7__44wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kj-uuaceq"/><path class="ta7__44wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-type2-48" /></template>
