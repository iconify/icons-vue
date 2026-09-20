<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soou_-bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soou_-bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:itheum" /></template>
