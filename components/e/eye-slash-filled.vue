<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl-4yzrgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl-4yzrgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eye-slash-filled" /></template>
