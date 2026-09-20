<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5tparb-y.css';
import '../../css/n/na_x8vbwq.css';
import '../../css/o/oezn8xk0e.css';
import '../../css/w/wos6is2ia.css';
import '../../css/q/qer_0rbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5tparb-y"/><path class="na_x8vbwq"/><path clip-rule="evenodd" class="oezn8xk0e"/><path class="wos6is2ia"/><path clip-rule="evenodd" class="qer_0rbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-share-light" /></template>
