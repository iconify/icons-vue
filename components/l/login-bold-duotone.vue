<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8y2-tvlr.css';
import '../../css/q/qzm6rmb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8y2-tvlr"/><path class="qzm6rmb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:login-bold-duotone" /></template>
