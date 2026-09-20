<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd1sf9boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd1sf9boo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-24" /></template>
