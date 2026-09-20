<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqvk4veur.css';
import '../../css/a/a1ey-7bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zqvk4veur"/><path class="a1ey-7bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bookmark-list-ltr" /></template>
