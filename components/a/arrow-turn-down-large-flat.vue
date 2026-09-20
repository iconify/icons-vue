<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5ry4ve3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z5ry4ve3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:arrow-turn-down-large-flat" /></template>
