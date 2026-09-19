<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz2zk-lcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tz2zk-lcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:link-bold" /></template>
