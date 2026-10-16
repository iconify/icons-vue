<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6ncrt0qq.css';
import '../../css/d/d6ggj99yx.css';
import '../../css/j/jofw17bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k6ncrt0qq"/><path class="d6ggj99yx"/><path class="jofw17bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:current-source-20" /></template>
