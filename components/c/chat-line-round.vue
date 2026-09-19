<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp2ifdcbr.css';
import '../../css/d/dn0-kucri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bp2ifdcbr"/><path class="dn0-kucri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:chat-line-round" /></template>
