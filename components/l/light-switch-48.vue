<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie-wxdblp.css';
import '../../css/t/tqdfodbmv.css';
import '../../css/p/p8s_xtbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ie-wxdblp"/><path class="tqdfodbmv"/><path class="p8s_xtbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:light-switch-48" /></template>
