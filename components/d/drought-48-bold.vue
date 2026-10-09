<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diqsj_bxu.css';
import '../../css/g/g0orui1mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="diqsj_bxu"/><path class="g0orui1mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drought-48-bold" /></template>
