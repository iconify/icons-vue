<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-hy31bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-hy31bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:butterfly" /></template>
