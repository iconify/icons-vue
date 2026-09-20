<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpd0j0tem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpd0j0tem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chart-trend-up-duotone" /></template>
