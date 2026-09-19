<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/kr1jb4bit.css';
import '../../css/b/bu32m9wsb.css';
import '../../css/p/p6__3lblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kr1jb4bit"/><path class="bu32m9wsb"/><path class="p6__3lblo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:folder-settings" /></template>
