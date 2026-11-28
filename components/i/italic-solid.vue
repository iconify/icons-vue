<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av7c2sb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av7c2sb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:italic-solid" /></template>
