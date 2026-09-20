<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmq08gb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmq08gb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-circle-line" /></template>
