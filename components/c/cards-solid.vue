<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3v2xclyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3v2xclyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cards-solid" /></template>
