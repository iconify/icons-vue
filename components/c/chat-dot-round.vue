<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp2ifdcbr.css';
import '../../css/b/b2kor1dzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bp2ifdcbr"/><path class="b2kor1dzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:chat-dot-round" /></template>
