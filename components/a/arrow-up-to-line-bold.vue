<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqe-1p3yw.css';
import '../../css/o/ohna_rbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqe-1p3yw"/><path class="ohna_rbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-to-line-bold" /></template>
