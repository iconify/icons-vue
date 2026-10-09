<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojno-rj8g.css';
import '../../css/i/iyti-7bea.css';
import '../../css/w/wi_h01enb.css';
import '../../css/f/fonho850d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ojno-rj8g"/><path class="iyti-7bea"/><path class="wi_h01enb"/><path class="fonho850d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-tank-48" /></template>
