<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn9u4nb1b.css';
import '../../css/r/r_rs3to2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn9u4nb1b"/><path class="r_rs3to2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bomb" /></template>
