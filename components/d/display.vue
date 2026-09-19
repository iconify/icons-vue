<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8pd91bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u8pd91bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:display" /></template>
