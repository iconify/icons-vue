<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajev8gbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ajev8gbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:expand" /></template>
