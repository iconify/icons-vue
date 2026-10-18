<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu4hgabyh.css';
import '../../css/p/pajsys7wq.css';
import '../../css/c/clnf1dbfu.css';
import '../../css/q/qx_f1tive.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eu4hgabyh"/><path class="pajsys7wq"/><path class="clnf1dbfu"/><path class="qx_f1tive"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-cooling-48-bold" /></template>
