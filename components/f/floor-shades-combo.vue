<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uigpp6_gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uigpp6_gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:floor-shades-combo" /></template>
