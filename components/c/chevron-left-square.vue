<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjd33qpzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjd33qpzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevron-left-square" /></template>
