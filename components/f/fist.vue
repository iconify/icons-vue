<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdwl95bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hdwl95bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:fist" /></template>
