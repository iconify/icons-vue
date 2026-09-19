<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxx79ebpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dxx79ebpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:arrow-up-outline" /></template>
