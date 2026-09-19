<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am1mhwe5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am1mhwe5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-calendar-star" /></template>
