<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1di2nq9t.css';
import '../../css/q/q4vtdtwun.css';
import '../../css/p/p7kyn66pi.css';
import '../../css/m/moupylo6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z1di2nq9t"/><path class="q4vtdtwun"/><path class="p7kyn66pi"/><path class="moupylo6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charger-48" /></template>
