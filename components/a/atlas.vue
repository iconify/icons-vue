<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8lx0vbrj.css';
import '../../css/v/vy0ldfbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8lx0vbrj"/><path class="vy0ldfbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:atlas" /></template>
