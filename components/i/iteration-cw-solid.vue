<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3oebeb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3oebeb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:iteration-cw-solid" /></template>
