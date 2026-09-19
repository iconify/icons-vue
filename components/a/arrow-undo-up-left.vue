<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysu_7yk8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ysu_7yk8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-undo-up-left" /></template>
