<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4r32990q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4r32990q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-big-up-gloss" /></template>
