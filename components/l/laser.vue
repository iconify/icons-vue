<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys0p6mg3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys0p6mg3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:laser" /></template>
