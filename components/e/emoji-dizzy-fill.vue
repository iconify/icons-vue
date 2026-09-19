<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn4-air-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zn4-air-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-dizzy-fill" /></template>
