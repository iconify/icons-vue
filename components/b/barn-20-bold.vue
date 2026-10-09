<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0106fblp.css';
import '../../css/v/vccof2b9q.css';
import '../../css/b/b8grcvrjy.css';
import '../../css/m/mtpfwtbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a0106fblp"/><path class="vccof2b9q"/><path class="b8grcvrjy"/><path class="mtpfwtbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barn-20-bold" /></template>
