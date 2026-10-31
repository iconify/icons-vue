<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts83b_9vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts83b_9vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fold-horizontal-fill-round" /></template>
