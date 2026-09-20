<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usxmd2bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usxmd2bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kucoin" /></template>
