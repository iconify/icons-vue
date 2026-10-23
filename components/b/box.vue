<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmenw7bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmenw7bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:box" /></template>
