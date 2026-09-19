<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_3y183aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b_3y183aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bold" /></template>
