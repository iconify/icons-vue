<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9-03fbxk.css';
import '../../css/z/zwafnhb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9-03fbxk"/><path class="zwafnhb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:alarm-on" /></template>
