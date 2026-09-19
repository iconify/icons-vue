<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou5lp3-8i.css';
import '../../css/f/fcfjhdcnf.css';
import '../../css/e/e7n2iruil.css';
import '../../css/q/qaayn7bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ou5lp3-8i"/><rect class="fcfjhdcnf"/><rect class="e7n2iruil"/><rect class="qaayn7bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bar-chart-outline" /></template>
