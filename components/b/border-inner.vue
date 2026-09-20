<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px063k46p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px063k46p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:border-inner" /></template>
