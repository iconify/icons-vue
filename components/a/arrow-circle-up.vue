<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn9svcbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn9svcbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-circle-up" /></template>
