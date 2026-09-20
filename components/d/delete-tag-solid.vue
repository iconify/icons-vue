<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1hjnz0to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y1hjnz0to"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:delete-tag-solid" /></template>
