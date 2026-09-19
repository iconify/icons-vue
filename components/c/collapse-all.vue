<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_-qmpv3t.css';
import '../../css/w/w-fhuabts.css';
import '../../css/v/vnkf6_bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w_-qmpv3t"/><path class="w-fhuabts"/><path class="vnkf6_bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:collapse-all" /></template>
