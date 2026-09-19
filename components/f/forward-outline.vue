<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxda01bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxda01bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:forward-outline" /></template>
