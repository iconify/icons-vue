<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxy3rfbfq.css';
import '../../css/k/kngzmjb8s.css';
import '../../css/e/eyyfu1tja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxy3rfbfq"/><path class="kngzmjb8s"/><path class="eyyfu1tja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:box-minimalistic-bold-duotone" /></template>
