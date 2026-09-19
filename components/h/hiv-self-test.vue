<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw0pzeiyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uw0pzeiyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hiv-self-test" /></template>
