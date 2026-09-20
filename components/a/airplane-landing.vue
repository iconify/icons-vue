<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzo8gfbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzo8gfbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:airplane-landing" /></template>
