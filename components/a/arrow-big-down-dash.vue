<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbgb1xbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbgb1xbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-big-down-dash" /></template>
