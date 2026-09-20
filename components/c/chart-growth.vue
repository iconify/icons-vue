<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuz3g9p4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuz3g9p4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:chart-growth" /></template>
