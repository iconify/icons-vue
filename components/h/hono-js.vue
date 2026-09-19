<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjg40r0in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjg40r0in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:hono-js" /></template>
