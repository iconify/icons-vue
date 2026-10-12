<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq1625qbk.css';
import '../../css/v/v0h99ub0p.css';
import '../../css/l/l9jgh7bvz.css';
import '../../css/s/st45emjbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vq1625qbk"/><path class="v0h99ub0p"/><path class="l9jgh7bvz"/><path class="st45emjbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clock-plus-48-bold" /></template>
