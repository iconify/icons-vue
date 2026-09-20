<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb7i6l95g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cb7i6l95g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cc-visa" /></template>
