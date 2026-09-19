<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxrd3hbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yxrd3hbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:half-circle" /></template>
