<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3j076bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3j076bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-2-filled" /></template>
