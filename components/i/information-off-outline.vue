<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkzi7gbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkzi7gbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:information-off-outline" /></template>
