<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxbqbtbyf.css';
import '../../css/n/n_ed3d90s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jxbqbtbyf"/><path class="n_ed3d90s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-analytics-outline" /></template>
