<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn_cutbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn_cutbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:battery-check" /></template>
