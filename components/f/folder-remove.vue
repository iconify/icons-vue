<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqtd-_a6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqtd-_a6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-remove" /></template>
