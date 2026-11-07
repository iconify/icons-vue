<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxna7-bqs.css';
import '../../css/e/edbk4g8dt.css';
import '../../css/x/xoc_r0_3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qxna7-bqs"/><path class="edbk4g8dt"/><path class="xoc_r0_3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-minimalistic-outline" /></template>
