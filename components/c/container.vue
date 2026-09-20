<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq2newv_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yq2newv_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:container" /></template>
