<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3lxiyb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j3lxiyb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-navigation-left-circle-1" /></template>
