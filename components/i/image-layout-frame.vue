<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrrnwgbhy.css';
import '../../css/o/od1iqpboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zrrnwgbhy"/><path class="od1iqpboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:image-layout-frame" /></template>
