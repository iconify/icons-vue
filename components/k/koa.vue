<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enoqhnb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enoqhnb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:koa" /></template>
