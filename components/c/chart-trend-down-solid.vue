<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo75l1ond.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo75l1ond"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chart-trend-down-solid" /></template>
