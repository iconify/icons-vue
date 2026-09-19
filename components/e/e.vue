<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keexsvbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="keexsvbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:e" /></template>
