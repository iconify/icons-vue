<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilkm3-gfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilkm3-gfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-long-up-right" /></template>
