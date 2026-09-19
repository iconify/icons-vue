<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hqkfeobqj.css';
import '../../css/e/e81n7dqey.css';
import '../../css/b/bo7xhxbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hqkfeobqj"/><path class="e81n7dqey"/><path clip-rule="evenodd" class="bo7xhxbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fill-color-solid" /></template>
