<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv1x4edtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nv1x4edtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:bookmark-filled" /></template>
