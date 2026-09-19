<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdcqx14cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdcqx14cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:loading-03" /></template>
