<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7r761b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o7r761b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fish-solid" /></template>
