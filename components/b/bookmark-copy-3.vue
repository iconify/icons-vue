<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9i3q3b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t9i3q3b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:bookmark-copy-3" /></template>
