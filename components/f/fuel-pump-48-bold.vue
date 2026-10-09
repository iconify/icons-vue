<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec_hp_w4i.css';
import '../../css/o/ort250bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ec_hp_w4i"/><path class="ort250bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-pump-48-bold" /></template>
