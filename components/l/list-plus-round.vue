<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybt0wbchx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybt0wbchx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-plus-round" /></template>
