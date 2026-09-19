<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy0e5mmid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy0e5mmid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-blanket" /></template>
