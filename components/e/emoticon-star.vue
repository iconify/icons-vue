<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugeu1-b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugeu1-b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-star" /></template>
