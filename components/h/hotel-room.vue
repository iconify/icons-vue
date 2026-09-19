<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l50cetj1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l50cetj1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:hotel-room" /></template>
