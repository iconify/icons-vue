<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymk6fnbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ymk6fnbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:closet-remix" /></template>
