<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgh__w-ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgh__w-ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:live-photo-line" /></template>
