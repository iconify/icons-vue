<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea9jj1p6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ea9jj1p6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-left" /></template>
