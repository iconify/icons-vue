<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxuijpbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxuijpbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bread-filled" /></template>
