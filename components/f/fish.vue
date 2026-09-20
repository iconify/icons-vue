<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jriao9pxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jriao9pxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:fish" /></template>
