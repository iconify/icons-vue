<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc78ikbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="lc78ikbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:krw" /></template>
