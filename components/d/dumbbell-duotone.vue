<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuf_yac1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wuf_yac1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dumbbell-duotone" /></template>
