<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmaeb6bkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xmaeb6bkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-medium-1" /></template>
