<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-zk5znxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-zk5znxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:browser-build" /></template>
