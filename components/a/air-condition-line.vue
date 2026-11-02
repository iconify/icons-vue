<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1hz6wm5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1hz6wm5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:air-condition-line" /></template>
