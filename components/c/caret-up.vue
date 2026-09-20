<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuw04zjab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zuw04zjab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:caret-up" /></template>
