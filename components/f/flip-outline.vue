<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdo2_9rnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdo2_9rnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:flip-outline" /></template>
