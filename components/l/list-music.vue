<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g84q8rbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g84q8rbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-music" /></template>
