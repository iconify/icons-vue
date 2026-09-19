<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw6szvbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zw6szvbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:calendar-fill" /></template>
