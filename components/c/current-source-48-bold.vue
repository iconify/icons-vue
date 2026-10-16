<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe8f_eb4j.css';
import '../../css/v/vjtl3vm_z.css';
import '../../css/k/krkzo_l8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qe8f_eb4j"/><path class="vjtl3vm_z"/><path class="krkzo_l8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:current-source-48-bold" /></template>
