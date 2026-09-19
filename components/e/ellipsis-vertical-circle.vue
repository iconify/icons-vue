<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yraf-tb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yraf-tb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:ellipsis-vertical-circle" /></template>
