<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pygc13kpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pygc13kpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disc-album-fill" /></template>
