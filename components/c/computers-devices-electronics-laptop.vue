<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol3a8ccys.css';
import '../../css/o/o_h18ib6j.css';
import '../../css/v/vdow_6bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ol3a8ccys"/><path class="o_h18ib6j"/><path class="vdow_6bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-laptop" /></template>
