<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0hnw-rab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0hnw-rab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-minus" /></template>
