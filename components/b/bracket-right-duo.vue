<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp7d6dfdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp7d6dfdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bracket-right-duo" /></template>
