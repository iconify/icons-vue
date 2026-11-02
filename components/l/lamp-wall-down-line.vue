<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lea21cbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lea21cbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lamp-wall-down-line" /></template>
