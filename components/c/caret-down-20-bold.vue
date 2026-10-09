<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrdqe2b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zrdqe2b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:caret-down-20-bold" /></template>
