<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzry2ab_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lzry2ab_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:leaf" /></template>
