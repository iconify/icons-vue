<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpczuhuaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rpczuhuaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-remove-fill" /></template>
