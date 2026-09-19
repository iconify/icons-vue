<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3gfwgnus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3gfwgnus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dock-left" /></template>
