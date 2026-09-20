<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-3ex_hwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-3ex_hwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-x" /></template>
