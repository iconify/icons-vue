<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwy2i44ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwy2i44ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beer-off-line" /></template>
