<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlxk5qbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlxk5qbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:flame-kindling-solid" /></template>
