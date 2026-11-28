<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpod5-wad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zpod5-wad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-compare-duotone" /></template>
