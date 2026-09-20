<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0-lr8ojg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0-lr8ojg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:list-bug-filled" /></template>
