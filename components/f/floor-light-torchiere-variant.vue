<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5-n9-bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5-n9-bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:floor-light-torchiere-variant" /></template>
