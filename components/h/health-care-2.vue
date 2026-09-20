<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnjb_7x4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qnjb_7x4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:health-care-2" /></template>
