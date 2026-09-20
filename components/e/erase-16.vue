<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-gd7u-dq.css';
import '../../css/a/a6o68sb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x-gd7u-dq"/><path clip-rule="evenodd" class="a6o68sb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:erase-16" /></template>
