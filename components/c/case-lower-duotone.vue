<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jelvk5ooi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jelvk5ooi primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:case-lower-duotone" /></template>
