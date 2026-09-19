<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu_q1hj4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu_q1hj4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-tone" /></template>
