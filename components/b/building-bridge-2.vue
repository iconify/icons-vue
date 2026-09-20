<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/padqvg4vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="padqvg4vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-bridge-2" /></template>
