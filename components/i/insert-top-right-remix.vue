<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3ttgpb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l3ttgpb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:insert-top-right-remix" /></template>
