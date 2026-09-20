<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww_qxgb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ww_qxgb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-minimalistic-outline" /></template>
