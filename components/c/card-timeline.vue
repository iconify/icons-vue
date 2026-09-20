<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu9d84atf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="yu9d84atf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:card-timeline" /></template>
