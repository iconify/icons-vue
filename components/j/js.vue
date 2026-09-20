<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2ml8t2kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x2ml8t2kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:js" /></template>
