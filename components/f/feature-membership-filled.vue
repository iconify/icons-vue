<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yes4g8bgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yes4g8bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:feature-membership-filled" /></template>
