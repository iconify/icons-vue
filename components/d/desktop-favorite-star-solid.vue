<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e151-8wyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e151-8wyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-favorite-star-solid" /></template>
