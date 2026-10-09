<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec_hp_w4i.css';
import '../../css/m/mh6unsbvq.css';
import '../../css/q/qk2_ljb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ec_hp_w4i"/><path class="mh6unsbvq"/><path class="qk2_ljb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-station-48-bold" /></template>
