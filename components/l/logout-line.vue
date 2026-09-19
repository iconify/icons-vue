<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oav658bbz.css';
import '../../css/v/v7yi4gwmc.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 oav658bbz"/><path class="clr-i-outline clr-i-outline-path-2 v7yi4gwmc"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:logout-line" /></template>
