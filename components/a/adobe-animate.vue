<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8cfp2b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w8cfp2b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-animate" /></template>
