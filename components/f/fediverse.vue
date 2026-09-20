<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6ntohbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ntohbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fediverse" /></template>
