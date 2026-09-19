<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuu17jmxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuu17jmxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-hi-precision-motion" /></template>
