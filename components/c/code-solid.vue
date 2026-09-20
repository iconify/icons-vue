<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/val914blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="val914blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:code-solid" /></template>
