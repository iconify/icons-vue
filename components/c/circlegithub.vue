<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yusms--8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1007};
const content = `<path class="yusms--8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlegithub" /></template>
