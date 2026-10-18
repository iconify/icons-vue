<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_56zubbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_56zubbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chart-pie" /></template>
