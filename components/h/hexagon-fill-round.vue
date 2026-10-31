<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt0hxmhgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt0hxmhgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-fill-round" /></template>
