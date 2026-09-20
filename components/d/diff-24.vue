<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j42lzccey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j42lzccey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-24" /></template>
