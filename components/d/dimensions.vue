<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj_czgbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jj_czgbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:dimensions" /></template>
