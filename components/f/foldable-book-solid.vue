<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1vxdrbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1vxdrbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:foldable-book-solid" /></template>
