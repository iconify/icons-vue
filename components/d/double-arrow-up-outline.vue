<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfur5nbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pfur5nbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:double-arrow-up-outline" /></template>
