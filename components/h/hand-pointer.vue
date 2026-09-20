<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kddf7p6ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kddf7p6ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-pointer" /></template>
