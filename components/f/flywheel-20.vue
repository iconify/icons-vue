<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrp-pcbtd.css';
import '../../css/e/evoi0uzhs.css';
import '../../css/k/k34k1_ice.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qrp-pcbtd"/><path class="evoi0uzhs"/><path class="k34k1_ice"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flywheel-20" /></template>
