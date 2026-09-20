<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqur2ubhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqur2ubhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bookmark-fill" /></template>
