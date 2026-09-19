<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tze189b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="tze189b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bing" /></template>
