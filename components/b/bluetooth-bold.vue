<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbw5dkbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbw5dkbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:bluetooth-bold" /></template>
