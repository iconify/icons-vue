<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mije3dbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mije3dbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:construction-outline" /></template>
