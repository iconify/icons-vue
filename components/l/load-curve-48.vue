<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv4k_bcjk.css';
import '../../css/k/kpfwnqb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dv4k_bcjk"/><path class="kpfwnqb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:load-curve-48" /></template>
