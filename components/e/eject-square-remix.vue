<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq_8xzbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gq_8xzbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:eject-square-remix" /></template>
