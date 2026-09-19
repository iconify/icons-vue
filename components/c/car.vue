<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4-3fab-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o4-3fab-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:car" /></template>
