<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1lv0ib9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1lv0ib9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloud" /></template>
