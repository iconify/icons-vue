<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijg5zh-jo.css';
import '../../css/w/wqbkv8u2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijg5zh-jo"/><path class="wqbkv8u2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:caret-up-circle" /></template>
