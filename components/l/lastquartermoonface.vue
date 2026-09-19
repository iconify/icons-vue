<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykltvrbat.css';
import '../../css/l/l6dxx07jx.css';
import '../../css/f/f9qpihbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ykltvrbat"/><path class="l6dxx07jx"/><path class="f9qpihbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:lastquartermoonface" /></template>
