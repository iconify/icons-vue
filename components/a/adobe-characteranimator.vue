<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wskg3bbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wskg3bbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-characteranimator" /></template>
