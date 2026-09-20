<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyuns3bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyuns3bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-off" /></template>
