<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaaaw1bso.css';
import '../../css/n/nlnn0ibiz.css';
import '../../css/x/xdrfk-b8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jaaaw1bso"/><path class="nlnn0ibiz"/><path class="xdrfk-b8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:add-location" /></template>
