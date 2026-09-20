<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1wfmlbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1wfmlbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:filter" /></template>
