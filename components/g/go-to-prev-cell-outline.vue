<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbloa41vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbloa41vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:go-to-prev-cell-outline" /></template>
