<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwo7qkb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="jwo7qkb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:deviantart" /></template>
