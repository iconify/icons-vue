<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i44s8reft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i44s8reft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:external-link" /></template>
