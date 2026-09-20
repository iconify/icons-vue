<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmlbocb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmlbocb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-high" /></template>
