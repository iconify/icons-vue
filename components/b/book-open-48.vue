<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we15u_h7x.css';
import '../../css/q/qg66_ubxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="we15u_h7x"/><path class="qg66_ubxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:book-open-48" /></template>
