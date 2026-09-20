<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q42og5bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q42og5bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-block-remix" /></template>
