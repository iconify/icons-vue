<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5elhacbk.css';
import '../../css/n/na_x8vbwq.css';
import '../../css/f/f_pnwq58d.css';
import '../../css/a/ar8blrbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5elhacbk"/><path class="na_x8vbwq"/><path clip-rule="evenodd" class="f_pnwq58d"/><path class="ar8blrbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-plus-light" /></template>
