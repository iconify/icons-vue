<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtzyn0b2b.css';
import '../../css/a/atyhtibwr.css';
import '../../css/b/bnq5ffb9n.css';
import '../../css/r/ranxahbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qtzyn0b2b"/><path class="atyhtibwr"/><path class="bnq5ffb9n"/><path class="ranxahbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-dashboard-48" /></template>
