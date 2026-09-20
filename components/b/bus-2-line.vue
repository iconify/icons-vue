<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2m2jwb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2m2jwb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bus-2-line" /></template>
