<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcpzrab3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcpzrab3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-add" /></template>
