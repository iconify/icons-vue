<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6h0z-b7o.css';
import '../../css/v/vkg5fb8sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6h0z-b7o"/><path class="vkg5fb8sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-round-minimalistic-bold-duotone" /></template>
