<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgbvxq5ir.css';
import '../../css/r/r7c5xu-gz.css';
import '../../css/t/to374yt6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rgbvxq5ir"/><path class="r7c5xu-gz"/><path class="to374yt6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-merge-20" /></template>
