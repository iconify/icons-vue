<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on9ysac7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on9ysac7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:corner-up-left" /></template>
