<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_-7pbckv.css';
import '../../css/p/p39fyrbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r_-7pbckv"/><path class="p39fyrbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:draught-proofing-48-bold" /></template>
