<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi3gcybrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi3gcybrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-x" /></template>
