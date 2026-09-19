<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7e4cpsjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t7e4cpsjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:chess-rook" /></template>
