<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pph593bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pph593bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:fold" /></template>
