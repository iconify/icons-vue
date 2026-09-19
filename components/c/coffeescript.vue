<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh0ih_lld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="jh0ih_lld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:coffeescript" /></template>
