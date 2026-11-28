<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niekoc4bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niekoc4bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:checkbox" /></template>
