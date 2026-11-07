<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf4ca1btm.css';
import '../../css/r/r_wkqfbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf4ca1btm"/><path class="r_wkqfbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:body-shape-bold-duotone" /></template>
