<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvhljtbdd.css';
import '../../css/y/ykb_zpbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nvhljtbdd"/><path class="ykb_zpbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:film" /></template>
