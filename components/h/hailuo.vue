<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhln_6f7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhln_6f7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hailuo" /></template>
