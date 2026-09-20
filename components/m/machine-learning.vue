<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycs1wjbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ycs1wjbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:machine-learning" /></template>
