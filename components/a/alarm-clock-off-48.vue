<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5mhtjb5j.css';
import '../../css/l/lnepfmblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w5mhtjb5j"/><path class="lnepfmblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alarm-clock-off-48" /></template>
