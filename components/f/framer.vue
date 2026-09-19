<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx2h32bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx2h32bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:framer" /></template>
