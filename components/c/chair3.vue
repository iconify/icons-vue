<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es4zrthkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es4zrthkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chair3" /></template>
