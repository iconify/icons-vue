<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd4bqtbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd4bqtbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-wrap-square" /></template>
