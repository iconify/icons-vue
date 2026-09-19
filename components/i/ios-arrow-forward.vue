<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0h0i5bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0h0i5bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-forward" /></template>
