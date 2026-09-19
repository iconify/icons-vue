<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqwy0pbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jqwy0pbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hand-support" /></template>
