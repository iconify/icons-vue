<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixi_e8amv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ixi_e8amv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:face-with-open-mouth-zerowidthjoiner-dash-symbol" /></template>
