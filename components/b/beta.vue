<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_0z7sb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_0z7sb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:beta" /></template>
