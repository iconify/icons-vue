<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq21qtbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq21qtbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bell-24" /></template>
