<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7olx61gw.css';
import '../../css/a/ary-4bknz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r7olx61gw"/><path class="ary-4bknz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-module-48" /></template>
