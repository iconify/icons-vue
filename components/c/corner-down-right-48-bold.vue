<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3__hfs6p.css';
import '../../css/z/zvtm7bcct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b3__hfs6p"/><path class="zvtm7bcct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-down-right-48-bold" /></template>
