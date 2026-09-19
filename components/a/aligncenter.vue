<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srz6vzznd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":644};
const content = `<path class="srz6vzznd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:aligncenter" /></template>
