<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psgtacb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psgtacb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:footprints" /></template>
