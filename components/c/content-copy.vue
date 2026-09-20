<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_x6d4blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_x6d4blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:content-copy" /></template>
