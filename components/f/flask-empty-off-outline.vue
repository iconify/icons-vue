<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj5jgybpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj5jgybpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flask-empty-off-outline" /></template>
