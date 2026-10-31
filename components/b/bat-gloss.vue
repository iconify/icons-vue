<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rci6ecb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rci6ecb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bat-gloss" /></template>
