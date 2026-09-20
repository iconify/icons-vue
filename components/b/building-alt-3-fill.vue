<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0xnzza0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0xnzza0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:building-alt-3-fill" /></template>
