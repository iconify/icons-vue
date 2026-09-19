<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqwvg3bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqwvg3bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:cloud" /></template>
