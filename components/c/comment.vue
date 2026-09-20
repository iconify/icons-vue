<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1_vj5bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f1_vj5bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:comment" /></template>
