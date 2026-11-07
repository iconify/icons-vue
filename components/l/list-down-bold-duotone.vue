<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ophijtbsv.css';
import '../../css/q/qg1_u7bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ophijtbsv"/><path class="qg1_u7bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-down-bold-duotone" /></template>
