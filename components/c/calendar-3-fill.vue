<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5ae-tbgb.css';
import '../../css/q/qeijpobfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5ae-tbgb"/><path class="qeijpobfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-3-fill" /></template>
