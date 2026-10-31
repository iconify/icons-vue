<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiow7sb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiow7sb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bed-gloss" /></template>
