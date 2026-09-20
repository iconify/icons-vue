<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkmasib7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkmasib7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-down-sharp-fill" /></template>
