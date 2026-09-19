<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnii4hccr.css';
import '../../css/s/sozjgdcyd.css';
import '../../css/x/xfox-b84f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="rnii4hccr"/><circle class="sozjgdcyd"/><path class="xfox-b84f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:help-buoy-outline" /></template>
