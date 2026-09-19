<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg6u5vbie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yg6u5vbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lifehalf" /></template>
