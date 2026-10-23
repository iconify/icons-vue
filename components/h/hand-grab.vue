<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6o-rbbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6o-rbbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hand-grab" /></template>
