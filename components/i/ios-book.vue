<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l99r3d5dl.css';
import '../../css/a/a4x7enbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l99r3d5dl"/><path class="a4x7enbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-book" /></template>
