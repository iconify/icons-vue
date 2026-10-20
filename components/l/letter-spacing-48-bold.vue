<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lstoyk0re.css';
import '../../css/s/s4l_bwbwm.css';
import '../../css/x/x5tz2lbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lstoyk0re"/><path class="s4l_bwbwm"/><path class="x5tz2lbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:letter-spacing-48-bold" /></template>
