<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1o-fsx4d.css';
import '../../css/p/pf54fdcpd.css';
import '../../css/o/otww_sbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o1o-fsx4d"/><path class="pf54fdcpd"/><path class="otww_sbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-branch-48-bold" /></template>
