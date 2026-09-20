<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlxct7buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zlxct7buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:home" /></template>
