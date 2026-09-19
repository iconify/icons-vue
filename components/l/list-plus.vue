<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrz4h5bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrz4h5bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:list-plus" /></template>
