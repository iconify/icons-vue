<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd_r1krus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wd_r1krus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flash-3" /></template>
