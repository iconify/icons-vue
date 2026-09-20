<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qby9oorro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qby9oorro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:flag3-filled" /></template>
