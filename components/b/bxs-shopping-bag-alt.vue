<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whiou-bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whiou-bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-shopping-bag-alt" /></template>
