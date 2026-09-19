<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yei9djbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yei9djbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:lightbulb" /></template>
