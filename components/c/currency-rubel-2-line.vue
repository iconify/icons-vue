<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxfx58bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxfx58bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-rubel-2-line" /></template>
