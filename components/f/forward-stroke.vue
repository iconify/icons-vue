<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaqkg9bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vaqkg9bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:forward-stroke" /></template>
