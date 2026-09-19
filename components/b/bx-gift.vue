<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oatn87bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oatn87bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-gift" /></template>
