<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v49x2_ycs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v49x2_ycs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:heart-check" /></template>
