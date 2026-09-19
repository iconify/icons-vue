<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it-zmj3wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it-zmj3wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:digg" /></template>
