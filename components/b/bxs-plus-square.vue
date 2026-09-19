<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1ogv8bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1ogv8bbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-plus-square" /></template>
