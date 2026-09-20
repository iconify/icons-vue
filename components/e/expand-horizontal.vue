<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0d8u222p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0d8u222p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:expand-horizontal" /></template>
