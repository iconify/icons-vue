<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmfs9bcfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hmfs9bcfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:favorite-star-fill" /></template>
