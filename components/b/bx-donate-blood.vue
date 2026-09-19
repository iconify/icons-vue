<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhcn3lz6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhcn3lz6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-donate-blood" /></template>
