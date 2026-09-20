<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on0f48l7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on0f48l7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:frame4-filled" /></template>
