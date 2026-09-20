<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czr71fe0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="czr71fe0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:archaeological-site-14" /></template>
