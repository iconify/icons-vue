<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtpr4ibiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gtpr4ibiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:hand-stop" /></template>
