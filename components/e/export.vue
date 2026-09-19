<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4s7seblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q4s7seblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:export" /></template>
