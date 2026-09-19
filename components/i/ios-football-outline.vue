<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf1qidbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yf1qidbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-football-outline" /></template>
