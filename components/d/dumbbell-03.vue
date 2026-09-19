<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juyn0yznl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juyn0yznl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dumbbell-03" /></template>
