<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le5mq_b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le5mq_b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:helicopter-2" /></template>
