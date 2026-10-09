<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es2omsi-m.css';
import '../../css/x/x_aucnmpg.css';
import '../../css/q/qga5sxbrw.css';
import '../../css/x/xf67hjb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="es2omsi-m"/><path class="x_aucnmpg"/><path class="qga5sxbrw"/><path class="xf67hjb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-tractor-20" /></template>
