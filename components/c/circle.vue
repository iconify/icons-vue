<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cacc3j1kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cacc3j1kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:circle" /></template>
