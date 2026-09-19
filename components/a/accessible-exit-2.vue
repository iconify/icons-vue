<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw80_35gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw80_35gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:accessible-exit-2" /></template>
