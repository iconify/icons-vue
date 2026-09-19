<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1barb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bc1barb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:camera-fill" /></template>
