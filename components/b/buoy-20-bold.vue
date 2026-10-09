<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyzks5_zi.css';
import '../../css/a/am6js3l0a.css';
import '../../css/l/lxo1cx_dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lyzks5_zi"/><path class="am6js3l0a"/><path class="lxo1cx_dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:buoy-20-bold" /></template>
