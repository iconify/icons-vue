<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb84m8s8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb84m8s8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bright" /></template>
