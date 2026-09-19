<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xecjju-9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xecjju-9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-heart-square" /></template>
