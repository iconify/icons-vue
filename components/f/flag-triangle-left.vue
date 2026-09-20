<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psqu8mbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psqu8mbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:flag-triangle-left" /></template>
