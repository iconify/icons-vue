<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mheydraer.css';
import '../../css/b/b4g0wlvcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mheydraer"/><path class="b4g0wlvcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flag-triangle-48-bold" /></template>
