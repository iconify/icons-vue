<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2o-9ho8x.css';
import '../../css/s/sl_3qvbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x2o-9ho8x"/><path class="sl_3qvbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drilling-rig-48-bold" /></template>
