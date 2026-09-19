<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxoh7_kwo.css';
import '../../css/j/jjd6ecb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxoh7_kwo"/><path class="jjd6ecb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:building-hospital" /></template>
