<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_54cfb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_54cfb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:localess-light" /></template>
