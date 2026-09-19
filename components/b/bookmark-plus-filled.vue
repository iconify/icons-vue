<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la3to1btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la3to1btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-plus-filled" /></template>
