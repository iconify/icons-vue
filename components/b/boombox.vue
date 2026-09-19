<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah5mw8brc.css';
import '../../css/t/tsy_4oboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah5mw8brc"/><path class="tsy_4oboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:boombox" /></template>
