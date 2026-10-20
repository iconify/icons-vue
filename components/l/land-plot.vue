<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibda_si-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibda_si-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:land-plot" /></template>
