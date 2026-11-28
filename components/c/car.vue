<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww1sdi6gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww1sdi6gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:car" /></template>
