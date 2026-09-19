<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb-69sr1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb-69sr1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:flip-vertical" /></template>
