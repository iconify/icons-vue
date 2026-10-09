<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ykncbhd.css';
import '../../css/c/c0d8b832j.css';
import '../../css/l/ln_qjmbiv.css';
import '../../css/m/m46n-bb2h.css';
import '../../css/o/ohpw7equm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w7ykncbhd"/><path class="c0d8b832j"/><path class="ln_qjmbiv"/><path class="m46n-bb2h"/><path class="ohpw7equm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-solar-48-bold" /></template>
