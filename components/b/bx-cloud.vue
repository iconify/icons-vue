<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwur23aoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwur23aoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-cloud" /></template>
