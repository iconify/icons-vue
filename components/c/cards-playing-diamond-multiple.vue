<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah2imfolq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah2imfolq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cards-playing-diamond-multiple" /></template>
