<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apss0ie4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apss0ie4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-small-line" /></template>
