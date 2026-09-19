<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm-x0nboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm-x0nboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:generic-car-charger" /></template>
