<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjp0w2bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjp0w2bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-down-za" /></template>
