<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rogpglb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rogpglb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-right-square" /></template>
