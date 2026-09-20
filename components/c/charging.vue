<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3k1gxm3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a3k1gxm3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:charging" /></template>
