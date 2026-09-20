<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwyqp9jxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwyqp9jxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:layers-minus" /></template>
