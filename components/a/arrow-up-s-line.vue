<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmkm7dbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmkm7dbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-s-line" /></template>
