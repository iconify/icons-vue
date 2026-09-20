<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjf-gv2gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjf-gv2gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:battery-full4-filled" /></template>
