<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/capfaguaf.css';
import '../../css/a/atabikbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="capfaguaf"/><path class="atabikbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:link" /></template>
