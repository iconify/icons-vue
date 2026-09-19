<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zod2l60ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zod2l60ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:book-bookmark-filled" /></template>
