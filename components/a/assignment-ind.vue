<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohe_6i2-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohe_6i2-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:assignment-ind" /></template>
