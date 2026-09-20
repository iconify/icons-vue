<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-ib_hblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-ib_hblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:all-terrain-vehicle" /></template>
