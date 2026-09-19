<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2d0i-b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2d0i-b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:beer-filled" /></template>
