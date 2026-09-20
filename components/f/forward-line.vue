<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlo2neb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlo2neb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forward-line" /></template>
