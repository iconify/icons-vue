<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmtkecamq.css';
import '../../css/v/vv-azsxen.css';
import '../../css/s/sqh4xjrbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nmtkecamq"/><path class="vv-azsxen"/><path class="sqh4xjrbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dial-indicator-48" /></template>
