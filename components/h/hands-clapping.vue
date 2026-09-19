<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7xkc2giq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7xkc2giq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hands-clapping" /></template>
