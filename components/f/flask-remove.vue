<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq1br_bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq1br_bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-remove" /></template>
