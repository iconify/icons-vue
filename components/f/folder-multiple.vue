<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg52-i0ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg52-i0ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:folder-multiple" /></template>
