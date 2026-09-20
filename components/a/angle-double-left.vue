<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnfswol-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnfswol-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:angle-double-left" /></template>
