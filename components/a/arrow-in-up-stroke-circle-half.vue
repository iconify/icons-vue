<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y360en5ri.css';
import '../../css/i/if80w2ton.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y360en5ri"/><path class="if80w2ton"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-up-stroke-circle-half" /></template>
