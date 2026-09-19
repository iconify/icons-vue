<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3q9u1byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3q9u1byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-traffic-cone" /></template>
