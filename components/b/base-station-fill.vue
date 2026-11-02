<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri_p3wqir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri_p3wqir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:base-station-fill" /></template>
