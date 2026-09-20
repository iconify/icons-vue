<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzjf2zbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zzjf2zbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-2-horizontal-end-sharp-fill" /></template>
