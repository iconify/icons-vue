<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fby0atbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fby0atbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-battery" /></template>
