<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sknxk9b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sknxk9b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:camera-wireless" /></template>
