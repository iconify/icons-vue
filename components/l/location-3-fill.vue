<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6fjbw84x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6fjbw84x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:location-3-fill" /></template>
