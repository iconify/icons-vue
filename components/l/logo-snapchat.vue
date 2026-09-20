<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8t6515-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c8t6515-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-snapchat" /></template>
