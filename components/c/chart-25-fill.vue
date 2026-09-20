<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y30mxi8-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y30mxi8-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-25-fill" /></template>
