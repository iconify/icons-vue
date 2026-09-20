<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akdc04zlf.css';
import '../../css/a/asob6ykds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="akdc04zlf"/><path class="asob6ykds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-hamburger" /></template>
