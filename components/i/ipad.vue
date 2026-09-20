<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx6-ytqrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jx6-ytqrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:ipad" /></template>
