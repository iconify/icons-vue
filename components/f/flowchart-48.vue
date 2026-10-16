<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu98hpkgc.css';
import '../../css/u/uu29n6b9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mu98hpkgc"/><path class="uu29n6b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flowchart-48" /></template>
