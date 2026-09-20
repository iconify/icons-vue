<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1ignbsnl.css';
import '../../css/g/g0qglybal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ignbsnl"/><path class="g0qglybal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:business-pearl-bold" /></template>
