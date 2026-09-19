<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4z4z2_dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":480};
const content = `<path class="y4z4z2_dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:badge-check" /></template>
