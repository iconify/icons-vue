<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh_7pnb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh_7pnb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:call-split" /></template>
