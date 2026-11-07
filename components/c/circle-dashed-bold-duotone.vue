<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9vvgn11d.css';
import '../../css/t/t52mucocr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9vvgn11d"/><path class="t52mucocr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-dashed-bold-duotone" /></template>
