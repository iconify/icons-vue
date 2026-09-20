<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj8_542oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj8_542oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:light-umbrella-reflect" /></template>
