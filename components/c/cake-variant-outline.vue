<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qert3hfpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qert3hfpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cake-variant-outline" /></template>
