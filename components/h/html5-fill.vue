<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv2cjxj3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv2cjxj3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:html5-fill" /></template>
