<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc_lbbcgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc_lbbcgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dolphin-dphnai" /></template>
