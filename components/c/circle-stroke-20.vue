<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yynfaacui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yynfaacui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-stroke-20" /></template>
