<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywvby7dss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywvby7dss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:diagonal-scroll-point-01" /></template>
