<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eie4fbbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eie4fbbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-open-search" /></template>
