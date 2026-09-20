<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q80-_p5dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q80-_p5dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-left-right-ellipsis" /></template>
