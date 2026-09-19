<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye5j1p-tl.css';
import '../../css/c/ca8-a7btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye5j1p-tl"/><path class="ca8-a7btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-rename" /></template>
