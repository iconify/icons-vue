<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr5k10bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kr5k10bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:glide-g" /></template>
