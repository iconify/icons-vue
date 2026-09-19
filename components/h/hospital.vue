<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kiwwtpb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="kiwwtpb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hospital" /></template>
