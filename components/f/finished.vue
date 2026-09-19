<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc0cjx2pv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wc0cjx2pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:finished" /></template>
