<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd8qvabnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cd8qvabnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:amount-up-two-outline" /></template>
