<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qssosskvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qssosskvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-6-fill" /></template>
