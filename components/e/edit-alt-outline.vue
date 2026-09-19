<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-w7s1bmt.css';
import '../../css/y/ys8pa0b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-w7s1bmt"/><path class="ys8pa0b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:edit-alt-outline" /></template>
