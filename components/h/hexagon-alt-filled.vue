<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9baqwbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9baqwbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hexagon-alt-filled" /></template>
