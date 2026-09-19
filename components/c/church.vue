<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx_nbgaic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fx_nbgaic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:church" /></template>
