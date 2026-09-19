<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja6d-8b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja6d-8b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:letter-spacing-alt" /></template>
