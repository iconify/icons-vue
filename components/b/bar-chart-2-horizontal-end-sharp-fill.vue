<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckuawubog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckuawubog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bar-chart-2-horizontal-end-sharp-fill" /></template>
