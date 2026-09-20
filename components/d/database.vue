<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb4qbkb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zb4qbkb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:database" /></template>
