<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw5w10zib.css';
import '../../css/s/s5u-maceu.css';
import '../../css/q/qkc80i2jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yw5w10zib"/><path class="s5u-maceu"/><path class="qkc80i2jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydro-turbine-48" /></template>
