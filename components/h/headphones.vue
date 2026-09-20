<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wio9zio-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wio9zio-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:headphones" /></template>
