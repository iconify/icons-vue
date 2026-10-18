<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8e9snbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8e9snbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloud" /></template>
