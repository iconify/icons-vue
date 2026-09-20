<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfbi3mbkc.css';
import '../../css/v/vs45rqbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfbi3mbkc"/><path clip-rule="evenodd" class="vs45rqbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:government-fill" /></template>
