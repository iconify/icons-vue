<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bidi4bbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bidi4bbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:cpu" /></template>
