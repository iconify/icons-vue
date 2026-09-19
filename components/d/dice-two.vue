<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj5v0cbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bj5v0cbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:dice-two" /></template>
