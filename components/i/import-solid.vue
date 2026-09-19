<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfh-ukf2y.css';
import '../../css/q/qo-gibb2p.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 wfh-ukf2y"/><path class="clr-i-solid clr-i-solid-path-2 qo-gibb2p"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:import-solid" /></template>
