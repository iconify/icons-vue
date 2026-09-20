<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j62-f-ylc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j62-f-ylc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hourglass-2-fill" /></template>
