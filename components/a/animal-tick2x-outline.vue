<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpn68nbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qpn68nbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-tick2x-outline" /></template>
