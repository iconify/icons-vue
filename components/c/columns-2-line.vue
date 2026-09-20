<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/osrqvu4up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osrqvu4up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:columns-2-line" /></template>
