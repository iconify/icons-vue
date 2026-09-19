<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4cmheptx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v4cmheptx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:chevron-up" /></template>
