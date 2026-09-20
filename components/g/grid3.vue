<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0rt58u6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0rt58u6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid3" /></template>
