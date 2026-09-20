<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2l9anbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="k2l9anbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:laptop-charging" /></template>
