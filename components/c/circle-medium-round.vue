<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0g0lp3_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0g0lp3_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-medium-round" /></template>
