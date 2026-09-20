<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6hkwsbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6hkwsbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:elastic" /></template>
