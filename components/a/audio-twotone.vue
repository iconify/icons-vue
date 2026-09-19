<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwft8icjo.css';
import '../../css/g/g3ep0ud-q.css';
import '../../css/k/k1nnfsbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iwft8icjo"/><path class="g3ep0ud-q"/><path class="k1nnfsbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:audio-twotone" /></template>
