<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_9y1rgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1_9y1rgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-letter-t-filled" /></template>
