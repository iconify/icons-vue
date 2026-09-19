<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7_yckbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7_yckbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-h1-1" /></template>
