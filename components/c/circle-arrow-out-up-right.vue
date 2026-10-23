<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcrzizbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcrzizbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-arrow-out-up-right" /></template>
