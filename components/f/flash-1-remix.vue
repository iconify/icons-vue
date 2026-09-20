<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aak4xjbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="aak4xjbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flash-1-remix" /></template>
