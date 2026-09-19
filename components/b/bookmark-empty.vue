<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf1l_yb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="wf1l_yb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:bookmark-empty" /></template>
