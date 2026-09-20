<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po7yq0b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="po7yq0b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-upright-three-quarter" /></template>
