<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdi9gst5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdi9gst5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:direction-right" /></template>
