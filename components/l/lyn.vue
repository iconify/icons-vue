<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5dc8kbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5dc8kbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:lyn" /></template>
