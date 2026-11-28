<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lud3zjb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lud3zjb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:level" /></template>
