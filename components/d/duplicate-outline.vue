<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1lbyxb3k.css';
import '../../css/d/ddsbg3vby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="x1lbyxb3k"/><path class="ddsbg3vby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:duplicate-outline" /></template>
