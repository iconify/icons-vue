<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx2t-v_0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rx2t-v_0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-horizontal-end-sharp-fill" /></template>
